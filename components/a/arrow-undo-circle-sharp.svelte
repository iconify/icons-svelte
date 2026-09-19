<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qshz47b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qshz47b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-undo-circle-sharp" {...props}></Icon>
