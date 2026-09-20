<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcu0ohh7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dcu0ohh7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:edit-cut" {...props}></Icon>
