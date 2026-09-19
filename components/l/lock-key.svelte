<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eukozub-p.css';
import '../../css/t/tnbv3bc-m.css';
import '../../css/j/j1g38rb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eukozub-p"/><path class="tnbv3bc-m"/><path class="j1g38rb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lock-key" {...props}></Icon>
