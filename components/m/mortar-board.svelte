<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_602diwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w_602diwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mortar-board" {...props}></Icon>
