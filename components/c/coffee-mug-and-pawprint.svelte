<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwhb53btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mwhb53btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffee-mug-and-pawprint" {...props}></Icon>
