<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap0-habhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap0-habhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-box-outline" {...props}></Icon>
