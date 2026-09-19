<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/piq9adp7d.css';
import '../../css/z/zh22fdwmm.css';
import '../../css/b/b8oitndok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="piq9adp7d"/><path class="zh22fdwmm"/><path class="b8oitndok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:printing-page" {...props}></Icon>
