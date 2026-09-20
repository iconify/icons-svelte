<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkqn_-bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bkqn_-bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-beside-conifer-tree-above-water" {...props}></Icon>
