<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it-qx-x1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="it-qx-x1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:db-ui-light" {...props}></Icon>
