<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u78g5fodw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u78g5fodw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:bookmark" {...props}></Icon>
