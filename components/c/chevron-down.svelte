<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5cii_bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5cii_bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down" {...props}></Icon>
