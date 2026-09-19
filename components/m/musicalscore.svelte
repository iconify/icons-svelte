<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2ubv2bis.css';
import '../../css/c/cbna_rb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2ubv2bis"/><path class="cbna_rb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:musicalscore" {...props}></Icon>
