<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on62zfi5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":721};
const content = `<path class="on62zfi5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:brush" {...props}></Icon>
