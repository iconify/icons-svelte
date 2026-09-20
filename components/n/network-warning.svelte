<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jjyi-2tjx.css';
import '../../css/c/c7ti4sbjw.css';
import '../../css/f/fll0uqb6i.css';
import '../../css/c/c59sr6bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jjyi-2tjx"/><path class="c7ti4sbjw"/><path class="fll0uqb6i"/><path class="c59sr6bdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-warning" {...props}></Icon>
