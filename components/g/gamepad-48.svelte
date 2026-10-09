<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxhse7b_h.css';
import '../../css/n/nyeck7_mh.css';
import '../../css/w/wsddmcbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yxhse7b_h"/><path class="nyeck7_mh"/><path class="wsddmcbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gamepad-48" {...props}></Icon>
