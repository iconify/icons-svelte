<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/ups30ep6k.css';
import '../../css/y/ydtkho0hx.css';
import '../../css/q/qc9g0cb4i.css';
import '../../css/a/ad6lxxbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ups30ep6k"/><path class="ydtkho0hx"/><path class="qc9g0cb4i"/><path class="ad6lxxbpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-open" {...props}></Icon>
