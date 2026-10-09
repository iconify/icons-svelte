<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w31fx27ee.css';
import '../../css/i/iorf4rbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w31fx27ee"/><path class="iorf4rbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pellet-boiler-48-bold" {...props}></Icon>
