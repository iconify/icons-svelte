<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox2dgjb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ox2dgjb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:exclamation-triangle" {...props}></Icon>
