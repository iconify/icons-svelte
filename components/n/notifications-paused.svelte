<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzyz4ebqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="vzyz4ebqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:notifications-paused" {...props}></Icon>
