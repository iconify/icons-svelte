<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gkk90rbam.css';
import '../../css/h/hxzmgwzjw.css';
import '../../css/b/bognoeqpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gkk90rbam"/><path class="hxzmgwzjw"/><path clip-rule="evenodd" class="bognoeqpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:internet" {...props}></Icon>
