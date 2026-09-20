<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khj3moalm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="khj3moalm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budget-board-light" {...props}></Icon>
