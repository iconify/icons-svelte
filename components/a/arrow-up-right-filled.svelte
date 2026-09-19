<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgfrq7b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgfrq7b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-right-filled" {...props}></Icon>
