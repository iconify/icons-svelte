<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv-w00b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rv-w00b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:donotdisturb" {...props}></Icon>
