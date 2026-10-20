<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9bgxeb0o.css';
import '../../css/c/ccjw-8b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y9bgxeb0o"/><path class="ccjw-8b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:line-height-20-bold" {...props}></Icon>
