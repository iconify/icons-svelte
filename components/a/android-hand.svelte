<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2ig19obm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2ig19obm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-hand" {...props}></Icon>
