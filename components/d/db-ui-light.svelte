<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4vwopt1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4vwopt1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:db-ui-light" {...props}></Icon>
