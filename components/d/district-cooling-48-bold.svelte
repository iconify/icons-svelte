<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0vjlubbx.css';
import '../../css/f/fp390_55c.css';
import '../../css/e/e7e9eebcd.css';
import '../../css/f/f5it5obaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0vjlubbx"/><path class="fp390_55c"/><path class="e7e9eebcd"/><path class="f5it5obaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:district-cooling-48-bold" {...props}></Icon>
