<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmzuscc9w.css';
import '../../css/o/oynddubhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fmzuscc9w"/><path class="oynddubhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-exit" {...props}></Icon>
