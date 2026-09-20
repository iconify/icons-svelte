<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bohhjnb0p.css';
import '../../css/h/hstms5foq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bohhjnb0p"/><path clip-rule="evenodd" class="hstms5foq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:png-solid" {...props}></Icon>
