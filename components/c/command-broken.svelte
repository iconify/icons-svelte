<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a1quj3bph.css';
import '../../css/w/w_9u0rbob.css';
import '../../css/c/czwys_6ab.css';
import '../../css/u/ulwx7ibev.css';
import '../../css/y/ypkivh3mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a1quj3bph"/><path class="w_9u0rbob"/><path class="czwys_6ab"/><path class="ulwx7ibev"/><path class="ypkivh3mh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:command-broken" {...props}></Icon>
