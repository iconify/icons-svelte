<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv6fu-bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hv6fu-bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-down-square-fill" {...props}></Icon>
