<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plpghf1-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plpghf1-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:globe-16" {...props}></Icon>
