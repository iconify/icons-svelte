<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoco9ob4a.css';
import '../../css/s/sa1x33xzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoco9ob4a"/><path class="sa1x33xzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:hospital-circle-fill" {...props}></Icon>
