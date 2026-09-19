<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uohs_2boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uohs_2boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackclubsuit" {...props}></Icon>
