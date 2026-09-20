<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_kx0ab8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a_kx0ab8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-branch-check-16" {...props}></Icon>
