<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtj-mrbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xtj-mrbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rack-ipc" {...props}></Icon>
