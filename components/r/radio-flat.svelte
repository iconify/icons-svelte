<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f9sbrvuos.css';
import '../../css/l/lb9wnv3nq.css';
import '../../css/d/dho87mbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f9sbrvuos"/><path clip-rule="evenodd" class="lb9wnv3nq"/><path class="dho87mbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:radio-flat" {...props}></Icon>
