<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1z4qnbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1z4qnbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mountain-view-filled" {...props}></Icon>
