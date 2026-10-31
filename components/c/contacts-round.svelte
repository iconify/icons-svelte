<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs-wccbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs-wccbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:contacts-round" {...props}></Icon>
