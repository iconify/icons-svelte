<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7npx6d9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y7npx6d9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:edit-outline" {...props}></Icon>
