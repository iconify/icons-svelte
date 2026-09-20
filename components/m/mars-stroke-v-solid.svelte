<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxt--gb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxt--gb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mars-stroke-v-solid" {...props}></Icon>
