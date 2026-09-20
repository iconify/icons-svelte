<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dhr1m1b7l.css';
import '../../css/l/l71ybw41v.css';
import '../../css/c/c5vk6tgit.css';
import '../../css/n/na52euwwy.css';
import '../../css/k/kkrotxg9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dhr1m1b7l"/><path class="l71ybw41v"/><path class="c5vk6tgit"/><path class="na52euwwy"/><path class="kkrotxg9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-2-linear" {...props}></Icon>
