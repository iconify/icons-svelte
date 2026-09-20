<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsv43wbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsv43wbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bio" {...props}></Icon>
