<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vms0ktmkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vms0ktmkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:balance-line" {...props}></Icon>
