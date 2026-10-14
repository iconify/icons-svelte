<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6chbzybu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t6chbzybu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dashboard-16" {...props}></Icon>
