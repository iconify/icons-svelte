<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zykn1z-dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zykn1z-dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mail-off" {...props}></Icon>
