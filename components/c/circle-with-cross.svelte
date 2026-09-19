<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5l_tybju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t5l_tybju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:circle-with-cross" {...props}></Icon>
