<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewh_gkbzz.css';
import '../../css/g/gjv7hdb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewh_gkbzz"/><path class="gjv7hdb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-up-20-bold" {...props}></Icon>
