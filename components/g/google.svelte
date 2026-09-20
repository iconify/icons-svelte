<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddiu6ubuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ddiu6ubuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:google" {...props}></Icon>
