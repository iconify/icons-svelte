<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/m/m8ytuwboy.css';
import '../../css/a/avtv4mbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="m8ytuwboy"/><path class="avtv4mbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-credit-20" {...props}></Icon>
