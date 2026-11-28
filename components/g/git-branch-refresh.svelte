<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woae21b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woae21b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:git-branch-refresh" {...props}></Icon>
