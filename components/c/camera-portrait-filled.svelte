<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm6zd0yms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm6zd0yms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-portrait-filled" {...props}></Icon>
