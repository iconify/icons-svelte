<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wly4zwo5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wly4zwo5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:building-small-filled" {...props}></Icon>
