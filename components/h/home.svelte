<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_3hubd1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="q_3hubd1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:home" {...props}></Icon>
