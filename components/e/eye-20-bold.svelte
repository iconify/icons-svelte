<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoe3avbru.css';
import '../../css/o/okm62lwzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yoe3avbru"/><path class="okm62lwzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-20-bold" {...props}></Icon>
