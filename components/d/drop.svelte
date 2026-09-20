<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heo0gqatv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="heo0gqatv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drop" {...props}></Icon>
