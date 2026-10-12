<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3y55cchp.css';
import '../../css/r/rkfducbyk.css';
import '../../css/v/vk46ucctf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s3y55cchp"/><path class="rkfducbyk"/><path class="vk46ucctf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:abacus-20" {...props}></Icon>
