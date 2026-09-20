<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9ml2l_nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9ml2l_nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nhl" {...props}></Icon>
