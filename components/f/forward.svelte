<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3n_jkbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3n_jkbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:forward" {...props}></Icon>
