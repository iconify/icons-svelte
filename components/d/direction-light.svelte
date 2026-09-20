<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/q/qa60wpbeh.css';
import '../../css/a/aescj0b_y.css';
import '../../css/z/zuii_hsfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="qa60wpbeh"/><path class="aescj0b_y"/><path class="zuii_hsfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:direction-light" {...props}></Icon>
