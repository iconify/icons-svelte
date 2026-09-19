<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us-2mi8ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="us-2mi8ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:lari-sign" {...props}></Icon>
