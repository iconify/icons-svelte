<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t56w-kbog.css';
import '../../css/d/dklul-ukq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t56w-kbog"/><path class="dklul-ukq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mug-tea" {...props}></Icon>
