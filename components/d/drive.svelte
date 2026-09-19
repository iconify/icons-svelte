<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc-_9ptfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lc-_9ptfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:drive" {...props}></Icon>
