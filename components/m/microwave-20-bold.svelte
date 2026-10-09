<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grlqybb5l.css';
import '../../css/q/q4-kh7ybm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="grlqybb5l"/><path class="q4-kh7ybm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microwave-20-bold" {...props}></Icon>
