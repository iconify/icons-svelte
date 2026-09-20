<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gile7j0jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gile7j0jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:payload-cms-light" {...props}></Icon>
