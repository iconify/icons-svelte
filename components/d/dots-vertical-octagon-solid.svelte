<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwk2iib2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwk2iib2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-octagon-solid" {...props}></Icon>
