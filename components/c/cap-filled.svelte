<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0hoqab8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0hoqab8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cap-filled" {...props}></Icon>
