<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq7pqabwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gq7pqabwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:download" {...props}></Icon>
