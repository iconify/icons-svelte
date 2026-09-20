<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft9ancbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ft9ancbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lego-outline" {...props}></Icon>
