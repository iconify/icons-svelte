<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx5q3876m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="lx5q3876m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-merge" {...props}></Icon>
