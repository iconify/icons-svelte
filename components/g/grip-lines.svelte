<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjv0mwbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mjv0mwbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grip-lines" {...props}></Icon>
