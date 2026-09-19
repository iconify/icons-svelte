<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_ebebtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="le_ebebtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:overleaf" {...props}></Icon>
