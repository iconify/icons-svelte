<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmo9ppb1i.css';
import '../../css/u/ugcs83bop.css';
import '../../css/m/m7ah4bbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lmo9ppb1i"><path class="ugcs83bop"/><path class="m7ah4bbgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:diagram-curve-up" {...props}></Icon>
