<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/acx96kbqj.css';
import '../../css/v/v5fixrg-m.css';
import '../../css/e/ed9fnw85i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="acx96kbqj"/><path class="v5fixrg-m"/><path class="ed9fnw85i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pc-firewall" {...props}></Icon>
