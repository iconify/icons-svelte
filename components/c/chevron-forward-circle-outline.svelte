<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybwzvccuq.css';
import '../../css/o/ozud7nbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybwzvccuq"/><path class="ozud7nbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-forward-circle-outline" {...props}></Icon>
