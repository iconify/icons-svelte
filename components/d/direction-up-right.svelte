<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdn3qrb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="wdn3qrb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-up-right" {...props}></Icon>
