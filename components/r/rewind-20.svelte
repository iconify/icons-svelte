<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2dd3q7hq.css';
import '../../css/m/msgtlpbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2dd3q7hq"/><path class="msgtlpbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rewind-20" {...props}></Icon>
