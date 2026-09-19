<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohvxbpr4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ohvxbpr4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:puzzle" {...props}></Icon>
