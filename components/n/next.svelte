<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6zwjkbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="p6zwjkbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:next" {...props}></Icon>
