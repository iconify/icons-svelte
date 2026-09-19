<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugyrdjbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugyrdjbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-rounded-dots" {...props}></Icon>
