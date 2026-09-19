<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fso1x3bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fso1x3bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fork-filled" {...props}></Icon>
