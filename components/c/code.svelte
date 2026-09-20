<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp5oe00ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp5oe00ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:code" {...props}></Icon>
