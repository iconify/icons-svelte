<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_q5z8bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_q5z8bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:home-sharp" {...props}></Icon>
