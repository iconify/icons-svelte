<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaia0tblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaia0tblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:engine-line" {...props}></Icon>
