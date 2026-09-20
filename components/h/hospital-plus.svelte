<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddk_lrtal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddk_lrtal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:hospital-plus" {...props}></Icon>
