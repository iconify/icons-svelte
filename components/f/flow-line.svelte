<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmxxkccbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cmxxkccbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flow-line" {...props}></Icon>
