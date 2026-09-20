<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6qv59w-v.css';
import '../../css/y/ypwg_3bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1113,"height":1225};
const content = `<path class="x6qv59w-v"/><path class="ypwg_3bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:howlerjs" {...props}></Icon>
