<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c5owlbcir.css';
import '../../css/n/nkf5_lt8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g transform="rotate(90 12 12)" class="ft5dv1b6b"><circle class="c5owlbcir"/><circle class="nkf5_lt8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:circle" {...props}></Icon>
