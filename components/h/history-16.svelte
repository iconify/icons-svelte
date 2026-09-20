<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfkp03q-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pfkp03q-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:history-16" {...props}></Icon>
