<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj2p-4bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj2p-4bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grab-solid" {...props}></Icon>
