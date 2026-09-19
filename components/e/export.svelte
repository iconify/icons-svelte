<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnd53nl8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gnd53nl8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:export" {...props}></Icon>
