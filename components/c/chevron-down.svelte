<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz2m8acdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="bz2m8acdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-down" {...props}></Icon>
