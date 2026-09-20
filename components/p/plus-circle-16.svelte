<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dicd2ghbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dicd2ghbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plus-circle-16" {...props}></Icon>
