<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g7k409bhs.css';
import '../../css/n/nqbip7m1a.css';
import '../../css/h/hbl-7rbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g7k409bhs"/><path class="nqbip7m1a"/><path class="hbl-7rbdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hot-tube" {...props}></Icon>
