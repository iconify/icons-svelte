<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/a8bwf-6ur.css';
import '../../css/u/uf4tivbrb.css';
import '../../css/t/tr5bubbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="a8bwf-6ur"/><path class="uf4tivbrb"/><path class="tr5bubbay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:psi-capital" {...props}></Icon>
