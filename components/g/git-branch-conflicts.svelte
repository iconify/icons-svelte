<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5xyyy2bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n5xyyy2bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-branch-conflicts" {...props}></Icon>
