<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg4igib2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gg4igib2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-16" {...props}></Icon>
