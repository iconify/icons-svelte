<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5i58z2mb.css';
import '../../css/m/mi4i07bgh.css';
import '../../css/j/jat07cb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d5i58z2mb"/><path class="mi4i07bgh"/><path class="jat07cb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:elderly-20" {...props}></Icon>
