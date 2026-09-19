<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxvd1fose.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bxvd1fose"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-happy-fill-16" {...props}></Icon>
