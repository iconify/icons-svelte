<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hth-q-b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hth-q-b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:ban" {...props}></Icon>
