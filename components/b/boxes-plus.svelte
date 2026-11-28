<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbpq97bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbpq97bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:boxes-plus" {...props}></Icon>
