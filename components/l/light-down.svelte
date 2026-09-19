<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0ii90bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0ii90bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:light-down" {...props}></Icon>
