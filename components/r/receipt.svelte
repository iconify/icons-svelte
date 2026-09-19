<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3-hujoeb.css';
import '../../css/w/w5cu6gb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3-hujoeb"/><path class="w5cu6gb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:receipt" {...props}></Icon>
