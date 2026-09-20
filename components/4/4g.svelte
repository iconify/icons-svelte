<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a230-oeew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a230-oeew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:4g" {...props}></Icon>
