<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji56rccna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ji56rccna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:fonts" {...props}></Icon>
