<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nybr-g8gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nybr-g8gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:more-2-line" {...props}></Icon>
