<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5i-ymejz.css';
import '../../css/x/xgar21b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i5i-ymejz"/><path class="xgar21b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hurricane-48" {...props}></Icon>
