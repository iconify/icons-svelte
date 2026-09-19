<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig19fbbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ig19fbbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:help-larrow" {...props}></Icon>
