<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oixmi4bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oixmi4bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:devices" {...props}></Icon>
