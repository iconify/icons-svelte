<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7--l_xes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7--l_xes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hourglass-fill" {...props}></Icon>
