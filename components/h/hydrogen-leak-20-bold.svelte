<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm8o83l5u.css';
import '../../css/a/ajmi_0bqu.css';
import '../../css/d/djpikibkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rm8o83l5u"/><path class="ajmi_0bqu"/><path class="djpikibkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-leak-20-bold" {...props}></Icon>
