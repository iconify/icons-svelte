<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqgpq5bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tqgpq5bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:laptop" {...props}></Icon>
