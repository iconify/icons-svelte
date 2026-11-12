<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvqnthbsg.css';
import '../../css/b/bh48ipmmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvqnthbsg"/><path class="bh48ipmmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raygun-monitoring-light" {...props}></Icon>
