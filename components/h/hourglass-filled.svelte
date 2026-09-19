<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dozf3_b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dozf3_b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hourglass-filled" {...props}></Icon>
