<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6q-f6bnh.css';
import '../../css/g/g0-4vd9sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6q-f6bnh"/><path class="g0-4vd9sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:meh" {...props}></Icon>
