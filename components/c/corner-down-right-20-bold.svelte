<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdmlx9xfd.css';
import '../../css/n/n4jpvghns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hdmlx9xfd"/><path class="n4jpvghns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-right-20-bold" {...props}></Icon>
