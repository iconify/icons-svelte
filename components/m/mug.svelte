<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dklul-ukq.css';
import '../../css/t/tgyzahb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dklul-ukq"/><path class="tgyzahb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mug" {...props}></Icon>
