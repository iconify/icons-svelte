<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4i5z2h2q.css';
import '../../css/c/c4uvzi6dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="j4i5z2h2q"/><path class="c4uvzi6dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pushover" {...props}></Icon>
