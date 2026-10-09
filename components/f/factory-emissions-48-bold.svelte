<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc93bwpoh.css';
import '../../css/s/sc1f8rb_h.css';
import '../../css/m/mo7b8rbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yc93bwpoh"/><path class="sc1f8rb_h"/><path class="mo7b8rbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:factory-emissions-48-bold" {...props}></Icon>
