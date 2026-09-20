<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkealni5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hkealni5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ip" {...props}></Icon>
