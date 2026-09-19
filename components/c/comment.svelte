<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4s7ccb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q4s7ccb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:comment" {...props}></Icon>
