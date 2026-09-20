<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4-1q-b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4-1q-b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-left-short-fill" {...props}></Icon>
