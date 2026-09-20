<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alg-2d_nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="alg-2d_nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:play-16" {...props}></Icon>
