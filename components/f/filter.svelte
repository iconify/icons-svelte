<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xai2kcsad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xai2kcsad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:filter" {...props}></Icon>
