<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otch78b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="otch78b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:moon" {...props}></Icon>
