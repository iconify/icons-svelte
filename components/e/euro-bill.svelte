<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu6q1ctkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="pu6q1ctkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:euro-bill" {...props}></Icon>
