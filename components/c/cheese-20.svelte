<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kps71gbrs.css';
import '../../css/z/zy_kdc0ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kps71gbrs"/><path class="zy_kdc0ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cheese-20" {...props}></Icon>
