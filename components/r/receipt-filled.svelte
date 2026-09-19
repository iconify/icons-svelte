<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuz_mbbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuz_mbbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:receipt-filled" {...props}></Icon>
