<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piij8abfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="piij8abfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-circle-sharp" {...props}></Icon>
