<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8a_wsmbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p8a_wsmbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:google" {...props}></Icon>
