<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baywupb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="baywupb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up-16" {...props}></Icon>
