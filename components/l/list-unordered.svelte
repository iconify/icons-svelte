<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofn0e2wdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="ofn0e2wdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:list-unordered" {...props}></Icon>
