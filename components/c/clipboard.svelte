<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk7emmcdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xk7emmcdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:clipboard" {...props}></Icon>
