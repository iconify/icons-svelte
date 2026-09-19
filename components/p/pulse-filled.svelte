<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsomblq2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsomblq2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pulse-filled" {...props}></Icon>
