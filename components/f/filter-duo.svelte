<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbz91zb-u.css';
import '../../css/x/xai2kcsad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbz91zb-u secondary"/><path class="primary xai2kcsad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:filter-duo" {...props}></Icon>
