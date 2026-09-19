<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo7aoqzxk.css';
import '../../css/l/l4be4thee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jo7aoqzxk"/><path class="l4be4thee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-email" {...props}></Icon>
