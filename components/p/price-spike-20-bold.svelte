<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01dflzvf.css';
import '../../css/q/qsbap5byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="qsbap5byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-spike-20-bold" {...props}></Icon>
