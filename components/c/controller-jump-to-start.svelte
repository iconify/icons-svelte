<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0qybk50m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h0qybk50m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:controller-jump-to-start" {...props}></Icon>
