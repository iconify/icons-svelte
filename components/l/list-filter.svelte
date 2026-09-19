<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poaev4p8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="poaev4p8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:list-filter" {...props}></Icon>
