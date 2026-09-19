<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgflwv-4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dgflwv-4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:plane" {...props}></Icon>
