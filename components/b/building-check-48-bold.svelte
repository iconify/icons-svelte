<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgo-bn5bm.css';
import '../../css/d/dsjehubcj.css';
import '../../css/d/d_u133t5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pgo-bn5bm"/><path class="dsjehubcj"/><path class="d_u133t5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-check-48-bold" {...props}></Icon>
