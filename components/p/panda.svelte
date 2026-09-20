<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v3z08obsy.css';
import '../../css/e/ewiisubuy.css';
import '../../css/a/a80bfbbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v3z08obsy"/><path class="ewiisubuy"/><path class="a80bfbbiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:panda" {...props}></Icon>
