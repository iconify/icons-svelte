<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtuvxgbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dtuvxgbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:line-fault-20" {...props}></Icon>
