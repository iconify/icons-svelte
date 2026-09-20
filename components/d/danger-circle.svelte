<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgfmpsboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgfmpsboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-circle" {...props}></Icon>
