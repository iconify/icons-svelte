<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzuh0_bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzuh0_bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:music-solid" {...props}></Icon>
