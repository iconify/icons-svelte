<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-323drdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-323drdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pilcrow-right" {...props}></Icon>
