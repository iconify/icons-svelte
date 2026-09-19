<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_3-2pbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_3-2pbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:american-football-sharp" {...props}></Icon>
