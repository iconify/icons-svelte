<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbcqh3bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mbcqh3bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:map-pin-outline" {...props}></Icon>
