<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni8m26bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ni8m26bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bell-fill-16" {...props}></Icon>
