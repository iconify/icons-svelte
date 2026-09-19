<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw1p922ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw1p922ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:airplane" {...props}></Icon>
