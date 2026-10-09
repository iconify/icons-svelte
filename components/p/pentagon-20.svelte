<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipdcptb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ipdcptb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pentagon-20" {...props}></Icon>
