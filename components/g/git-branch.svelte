<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd82cvbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sd82cvbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-branch" {...props}></Icon>
