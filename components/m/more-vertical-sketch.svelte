<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nucez9s0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nucez9s0v wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-vertical-sketch" {...props}></Icon>
