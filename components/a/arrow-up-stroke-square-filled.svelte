<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc0z2hpjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc0z2hpjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-stroke-square-filled" {...props}></Icon>
