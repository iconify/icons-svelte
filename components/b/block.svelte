<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzazxer1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xzazxer1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:block" {...props}></Icon>
