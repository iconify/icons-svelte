<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9c2ncydo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9c2ncydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-forked-16" {...props}></Icon>
