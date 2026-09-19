<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k0lno9bgx.css';
import '../../css/w/wzx-5xvic.css';
import '../../css/q/qk3kdsbng.css';
import '../../css/p/pzlrmg6rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="k0lno9bgx"/><path class="wzx-5xvic"/><path class="qk3kdsbng"/><path class="pzlrmg6rc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:oil-barrel" {...props}></Icon>
