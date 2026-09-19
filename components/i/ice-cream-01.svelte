<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e6zwofhca.css';
import '../../css/r/r4f-rbb3p.css';
import '../../css/b/b7eg75l7y.css';
import '../../css/q/qabuu-bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e6zwofhca"/><path class="r4f-rbb3p"/><path class="b7eg75l7y"/><path class="qabuu-bzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ice-cream-01" {...props}></Icon>
