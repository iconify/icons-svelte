<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxv1t9l-s.css';
import '../../css/t/tlriecbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nxv1t9l-s"/><path class="tlriecbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:piggy-bank-20-bold" {...props}></Icon>
