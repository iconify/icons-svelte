<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2kcaweza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2kcaweza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:notification" {...props}></Icon>
