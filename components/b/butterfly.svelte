<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u41ngwb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u41ngwb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:butterfly" {...props}></Icon>
