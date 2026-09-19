<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6go8hb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x6go8hb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:blackboard" {...props}></Icon>
