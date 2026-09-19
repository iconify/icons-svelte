<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q51s_lb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q51s_lb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dharmachakra" {...props}></Icon>
