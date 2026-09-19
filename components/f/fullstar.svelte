<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiyajtbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":961};
const content = `<path class="uiyajtbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fullstar" {...props}></Icon>
