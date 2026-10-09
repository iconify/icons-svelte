<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn8qmrq_l.css';
import '../../css/z/z_1yk_sgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nn8qmrq_l"/><path class="z_1yk_sgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eraser-48-bold" {...props}></Icon>
