<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psoacabks.css';
import '../../css/w/wtf21ym8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="psoacabks"/><path class="wtf21ym8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hard-hat-20-bold" {...props}></Icon>
