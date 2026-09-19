<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_guwunvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c_guwunvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:icloud" {...props}></Icon>
