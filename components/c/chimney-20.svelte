<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhjg018pp.css';
import '../../css/a/a0pyaabma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fhjg018pp"/><path class="a0pyaabma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chimney-20" {...props}></Icon>
