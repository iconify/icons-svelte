<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0ne4_zha.css';
import '../../css/v/vltx34bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k0ne4_zha"/><path class="vltx34bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-list-20-bold" {...props}></Icon>
