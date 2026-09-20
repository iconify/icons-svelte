<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn24bac4r.css';
import '../../css/x/xe3lk6bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nn24bac4r"/><path class="xe3lk6bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copilot-warning-16" {...props}></Icon>
