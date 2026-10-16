<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr83kubtu.css';
import '../../css/f/fyjv8ddts.css';
import '../../css/x/x5aslfb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gr83kubtu"/><path class="fyjv8ddts"/><path class="x5aslfb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:agv-20-bold" {...props}></Icon>
