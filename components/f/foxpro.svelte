<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2dw42tyk.css';
import '../../css/n/n9q2ej5ie.css';
import '../../css/m/mnz3z3wzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="c2dw42tyk"/><path class="n9q2ej5ie"/><path class="mnz3z3wzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:foxpro" {...props}></Icon>
