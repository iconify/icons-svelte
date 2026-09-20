<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trlk_bt4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="trlk_bt4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:crosshair-2" {...props}></Icon>
