<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlktqpbzo.css';
import '../../css/k/kif_tcbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mlktqpbzo"/><path class="kif_tcbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:erlenmeyer-flask" {...props}></Icon>
