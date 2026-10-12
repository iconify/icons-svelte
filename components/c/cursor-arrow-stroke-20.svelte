<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj44subkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qj44subkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cursor-arrow-stroke-20" {...props}></Icon>
