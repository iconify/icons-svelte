<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou2f5gbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ou2f5gbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:pin" {...props}></Icon>
