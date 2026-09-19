<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goo9ribrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="goo9ribrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:github-fill-16" {...props}></Icon>
