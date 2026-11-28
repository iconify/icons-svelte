<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk4c41b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk4c41b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pipe-duo" {...props}></Icon>
