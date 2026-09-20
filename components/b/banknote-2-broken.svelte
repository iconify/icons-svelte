<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n54zvri0c.css';
import '../../css/c/c5vk6tgit.css';
import '../../css/n/na52euwwy.css';
import '../../css/k/kkrotxg9c.css';
import '../../css/c/c5mjns4ur.css';
import '../../css/v/vxj36_bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n54zvri0c"/><path class="c5vk6tgit"/><path class="na52euwwy"/><path class="kkrotxg9c"/><path class="c5mjns4ur"/><path class="vxj36_bej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-2-broken" {...props}></Icon>
