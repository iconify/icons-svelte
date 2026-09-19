<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4dm_8boq.css';
import '../../css/s/swzjqgj-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s4dm_8boq"/><circle class="swzjqgj-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alert-warning-stroke-12" {...props}></Icon>
