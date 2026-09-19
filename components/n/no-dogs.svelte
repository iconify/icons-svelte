<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3t5tecsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="p3t5tecsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:no-dogs" {...props}></Icon>
