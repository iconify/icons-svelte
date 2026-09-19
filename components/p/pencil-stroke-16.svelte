<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikmultb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ikmultb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-stroke-16" {...props}></Icon>
