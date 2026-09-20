<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg9hjobky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9hjobky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anthropic-dark" {...props}></Icon>
