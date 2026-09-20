<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihv-_1bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ihv-_1bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:collumn" {...props}></Icon>
