<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmzlr3bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmzlr3bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:git-branch-plus" {...props}></Icon>
