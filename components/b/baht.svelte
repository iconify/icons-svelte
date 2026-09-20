<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvzy_sbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jvzy_sbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:baht" {...props}></Icon>
