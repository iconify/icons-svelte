<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o44li7u2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o44li7u2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:node-graph-root" {...props}></Icon>
