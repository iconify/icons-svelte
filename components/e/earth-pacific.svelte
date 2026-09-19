<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ndi7deu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="e7ndi7deu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-pacific" {...props}></Icon>
