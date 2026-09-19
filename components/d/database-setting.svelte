<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mwz9-fkga.css';
import '../../css/e/ehhtfzb3b.css';
import '../../css/o/o_egw1vkx.css';
import '../../css/v/vygavxbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="mwz9-fkga"/><path class="ehhtfzb3b"/><path class="o_egw1vkx"/><path class="vygavxbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database-setting" {...props}></Icon>
