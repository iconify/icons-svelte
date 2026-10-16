<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01dflzvf.css';
import '../../css/m/m4k8fxb9u.css';
import '../../css/q/q3l70xbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="m4k8fxb9u"/><path class="q3l70xbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:merit-order-20-bold" {...props}></Icon>
