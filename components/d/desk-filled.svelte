<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl8spzfjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl8spzfjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:desk-filled" {...props}></Icon>
