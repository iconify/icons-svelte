<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emd2oxpxc.css';
import '../../css/x/xtzb6uzhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emd2oxpxc"/><path class="xtzb6uzhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:capacitor-20-bold" {...props}></Icon>
