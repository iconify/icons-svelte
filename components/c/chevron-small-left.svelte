<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_82urleq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s_82urleq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-small-left" {...props}></Icon>
