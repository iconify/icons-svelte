<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bziph_bdn.css';
import '../../css/t/tbfod3hgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bziph_bdn"/><rect class="tbfod3hgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chevron-left-square" {...props}></Icon>
