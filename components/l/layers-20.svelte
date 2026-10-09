<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbzawxtfe.css';
import '../../css/f/fhe_vac-v.css';
import '../../css/g/gifn9ew9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lbzawxtfe"/><path class="fhe_vac-v"/><path class="gifn9ew9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layers-20" {...props}></Icon>
