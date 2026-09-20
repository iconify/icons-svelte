<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqaljb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kjqaljb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:browser-16" {...props}></Icon>
