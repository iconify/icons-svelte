<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gul0xinhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gul0xinhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folders-x" {...props}></Icon>
