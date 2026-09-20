<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsd5u-_9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsd5u-_9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-x-box-outline" {...props}></Icon>
