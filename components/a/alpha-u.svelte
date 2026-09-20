<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7_lt50pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7_lt50pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-u" {...props}></Icon>
