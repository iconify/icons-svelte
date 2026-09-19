<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7-w7-baa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c7-w7-baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-chevron-down-12" {...props}></Icon>
