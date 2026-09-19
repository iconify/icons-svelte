<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvcq89ble.css';
import '../../css/i/iip0rz5nl.css';
import '../../css/o/oqq-bg_3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cvcq89ble"><path class="iip0rz5nl"/><path class="oqq-bg_3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:dart-generated" {...props}></Icon>
