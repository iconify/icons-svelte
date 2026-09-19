<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phux6hbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":82,"height":690};
const content = `<path class="phux6hbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:i" {...props}></Icon>
