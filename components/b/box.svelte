<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkk7ktbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dkk7ktbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:box" {...props}></Icon>
