<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5whqinzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="w5whqinzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:people-arrows-left-right" {...props}></Icon>
