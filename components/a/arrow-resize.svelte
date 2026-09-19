<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utly6nbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utly6nbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-resize" {...props}></Icon>
