<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wra2vxbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wra2vxbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chevron-left" {...props}></Icon>
