<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/u79qfhp1l.css';
import '../../css/w/womghjzhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="u79qfhp1l"/><path clip-rule="evenodd" class="womghjzhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:address-book-outline" {...props}></Icon>
