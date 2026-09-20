<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-zmge8xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q-zmge8xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linkedin" {...props}></Icon>
