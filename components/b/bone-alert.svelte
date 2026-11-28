<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wimvd-lkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wimvd-lkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bone-alert" {...props}></Icon>
