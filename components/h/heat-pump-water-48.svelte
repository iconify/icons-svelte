<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yph0dvbon.css';
import '../../css/x/xezngbb0n.css';
import '../../css/g/gny111bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yph0dvbon"/><path class="xezngbb0n"/><path class="gny111bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-water-48" {...props}></Icon>
