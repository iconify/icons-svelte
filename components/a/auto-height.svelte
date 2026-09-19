<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thx-2abgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="thx-2abgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:auto-height" {...props}></Icon>
