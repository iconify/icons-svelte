<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvv1albfv.css';
import '../../css/c/c8g41rsjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvv1albfv"/><path clip-rule="evenodd" class="c8g41rsjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plate-bold" {...props}></Icon>
