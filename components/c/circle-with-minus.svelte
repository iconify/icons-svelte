<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwq9ehguz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cwq9ehguz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:circle-with-minus" {...props}></Icon>
