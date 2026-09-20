<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-n6wya5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v-n6wya5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:paint-roller" {...props}></Icon>
