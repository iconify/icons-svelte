<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asegpn4nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="asegpn4nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-511" {...props}></Icon>
