<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz8-ezbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iz8-ezbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-up-20-bold" {...props}></Icon>
