<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfxy13bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xfxy13bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:road-20-bold" {...props}></Icon>
