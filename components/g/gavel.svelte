<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nngue2ksh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nngue2ksh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:gavel" {...props}></Icon>
