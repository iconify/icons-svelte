<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t31bmlbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t31bmlbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-down-right-round" {...props}></Icon>
