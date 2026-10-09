<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxsoire1d.css';
import '../../css/j/jy-i8_pkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kxsoire1d"/><path class="jy-i8_pkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-48-bold" {...props}></Icon>
