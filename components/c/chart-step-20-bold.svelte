<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01dflzvf.css';
import '../../css/k/kmv2i6xfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="kmv2i6xfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-step-20-bold" {...props}></Icon>
