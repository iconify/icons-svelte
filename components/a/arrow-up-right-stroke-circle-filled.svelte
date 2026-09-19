<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtshnyb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtshnyb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-right-stroke-circle-filled" {...props}></Icon>
