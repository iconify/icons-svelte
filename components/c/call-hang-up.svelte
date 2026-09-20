<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv1-teoia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fv1-teoia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:call-hang-up" {...props}></Icon>
