<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge7rpwnsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ge7rpwnsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:flag" {...props}></Icon>
