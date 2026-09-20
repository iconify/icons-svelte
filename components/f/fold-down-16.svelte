<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w05rj732j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w05rj732j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:fold-down-16" {...props}></Icon>
