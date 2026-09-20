<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtyp_jihh.css';
import '../../css/f/fh3kbwobr.css';
import '../../css/q/q7cll_b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtyp_jihh"/><path class="fh3kbwobr"/><path clip-rule="evenodd" class="q7cll_b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-date-duotone" {...props}></Icon>
