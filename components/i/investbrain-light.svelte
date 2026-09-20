<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfnx0uh3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfnx0uh3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:investbrain-light" {...props}></Icon>
