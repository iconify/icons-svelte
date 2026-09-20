<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptf8xy91h.css';
import '../../css/m/m5ugsmtmc.css';
import '../../css/x/xwycoosoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ptf8xy91h"/><path class="m5ugsmtmc"/><circle class="xwycoosoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pawn" {...props}></Icon>
