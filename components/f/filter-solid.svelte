<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghen1wb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghen1wb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:filter-solid" {...props}></Icon>
