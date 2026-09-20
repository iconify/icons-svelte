<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2d--yqkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="u2d--yqkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-forked" {...props}></Icon>
