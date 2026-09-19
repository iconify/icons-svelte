<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn57cxbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mn57cxbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:dribbble" {...props}></Icon>
