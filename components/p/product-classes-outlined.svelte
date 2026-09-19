<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egw0_e_yk.css';
import '../../css/g/grhwfqo-l.css';
import '../../css/u/uxmpfhdsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="egw0_e_yk"/><path class="grhwfqo-l"/><path class="uxmpfhdsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:product-classes-outlined" {...props}></Icon>
