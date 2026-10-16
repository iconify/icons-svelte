<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_bbmbbxq.css';
import '../../css/b/b9xdq3bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c_bbmbbxq"/><path class="b9xdq3bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-joint-20" {...props}></Icon>
