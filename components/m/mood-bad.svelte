<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6q-f6bnh.css';
import '../../css/z/z7n81bcbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6q-f6bnh"/><path class="z7n81bcbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mood-bad" {...props}></Icon>
