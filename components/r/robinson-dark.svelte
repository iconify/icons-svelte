<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om1xn7ejk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="om1xn7ejk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:robinson-dark" {...props}></Icon>
