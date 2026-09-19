<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjvv51b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sjvv51b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flag" {...props}></Icon>
