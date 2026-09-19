<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcebpw6vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fcebpw6vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid-3x2" {...props}></Icon>
