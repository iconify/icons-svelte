<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pw778mbpo.css';
import '../../css/n/n-fw9sbnf.css';
import '../../css/g/gqayovb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pw778mbpo"/><circle class="n-fw9sbnf"/><path class="gqayovb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:metronome" {...props}></Icon>
