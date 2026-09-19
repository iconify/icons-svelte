<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jevk7xbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jevk7xbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:exclamation-triangle-fill" {...props}></Icon>
