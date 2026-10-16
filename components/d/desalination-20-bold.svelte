<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7m1t5brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w7m1t5brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desalination-20-bold" {...props}></Icon>
