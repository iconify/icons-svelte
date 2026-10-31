<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6j9kxb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6j9kxb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-5-fill-round" {...props}></Icon>
