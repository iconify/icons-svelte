<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2fvkrbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m2fvkrbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-beside-person-above-station-wagon" {...props}></Icon>
