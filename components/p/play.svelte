<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvebwk29s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pvebwk29s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:play" {...props}></Icon>
