<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9ytizxvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q9ytizxvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rewind-circle-outline" {...props}></Icon>
