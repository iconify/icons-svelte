<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-0hme5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ie-0hme5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:heart" {...props}></Icon>
