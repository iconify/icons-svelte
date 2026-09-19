<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7h3fsbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h7h3fsbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-with-circle-left" {...props}></Icon>
