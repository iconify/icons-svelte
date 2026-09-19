<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trxi2bbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trxi2bbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-right-filled" {...props}></Icon>
