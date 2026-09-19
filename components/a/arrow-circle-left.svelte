<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr5s_x-nn.css';
import '../../css/b/bqij9q-9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mr5s_x-nn"/><path class="bqij9q-9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-circle-left" {...props}></Icon>
