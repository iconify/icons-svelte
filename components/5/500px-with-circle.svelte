<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j03_z294p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j03_z294p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:500px-with-circle" {...props}></Icon>
