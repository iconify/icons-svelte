<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql33l8pgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql33l8pgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:perm-identity" {...props}></Icon>
