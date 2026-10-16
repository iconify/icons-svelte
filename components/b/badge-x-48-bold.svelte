<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si1030bhs.css';
import '../../css/t/tozua4tpq.css';
import '../../css/z/zebyaelmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si1030bhs"/><path class="tozua4tpq"/><path class="zebyaelmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-x-48-bold" {...props}></Icon>
