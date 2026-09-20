<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leow5mbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="leow5mbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-shrink-diagonal-1" {...props}></Icon>
