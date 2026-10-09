<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jed2ayb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jed2ayb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-circle-20" {...props}></Icon>
