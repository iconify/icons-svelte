<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf-4vfz_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-4vfz_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dashboard" {...props}></Icon>
