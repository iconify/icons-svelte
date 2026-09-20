<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d625uvbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d625uvbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dove-above-outstretched-hand" {...props}></Icon>
