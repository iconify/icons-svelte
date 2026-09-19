<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3une8b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3une8b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-sad-stroke-16" {...props}></Icon>
