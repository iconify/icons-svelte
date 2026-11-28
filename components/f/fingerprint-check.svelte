<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfa9x7v7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfa9x7v7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fingerprint-check" {...props}></Icon>
