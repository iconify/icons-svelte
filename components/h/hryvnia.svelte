<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx864zbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gx864zbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hryvnia" {...props}></Icon>
