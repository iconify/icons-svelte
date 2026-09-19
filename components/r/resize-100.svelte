<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2-mbfr7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q2-mbfr7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:resize-100" {...props}></Icon>
