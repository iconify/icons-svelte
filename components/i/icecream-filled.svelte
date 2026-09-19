<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doqq05v5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doqq05v5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:icecream-filled" {...props}></Icon>
