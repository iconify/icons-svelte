<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csxpon4lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="csxpon4lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:database" {...props}></Icon>
