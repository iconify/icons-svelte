<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlj17obtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qlj17obtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glpi-dark" {...props}></Icon>
