<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2o_fgbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e2o_fgbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up-right-16" {...props}></Icon>
