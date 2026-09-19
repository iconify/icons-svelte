<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdo805--h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jdo805--h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:maximize-fill-16" {...props}></Icon>
