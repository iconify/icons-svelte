<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1brf6mxa.css';
import '../../css/x/xou2jbzza.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s1brf6mxa"/><path class="xou2jbzza"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-check-48" {...props}></Icon>
