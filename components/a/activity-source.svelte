<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swn4cmbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="swn4cmbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:activity-source" {...props}></Icon>
