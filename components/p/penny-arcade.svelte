<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8mbytblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c8mbytblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:penny-arcade" {...props}></Icon>
