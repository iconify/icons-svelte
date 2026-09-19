<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpik4gbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rpik4gbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-activitybar-right" {...props}></Icon>
