<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzp9m4bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kzp9m4bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:python-logo-yellow" {...props}></Icon>
