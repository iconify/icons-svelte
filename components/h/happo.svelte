<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt4mkab9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kt4mkab9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:happo" {...props}></Icon>
