<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkrbc7bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jkrbc7bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:dialpad" {...props}></Icon>
