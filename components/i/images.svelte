<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihv80ibov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ihv80ibov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:images" {...props}></Icon>
