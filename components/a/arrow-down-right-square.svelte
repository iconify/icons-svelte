<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xjpqbwb8y.css';
import '../../css/z/zn7tbabdp.css';
import '../../css/t/tbfod3hgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xjpqbwb8y"/><path class="zn7tbabdp"/><rect class="tbfod3hgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-down-right-square" {...props}></Icon>
