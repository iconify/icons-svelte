<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7_t3jbcz.css';
import '../../css/u/u2b-m9bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y7_t3jbcz"/><path class="u2b-m9bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbubbles" {...props}></Icon>
