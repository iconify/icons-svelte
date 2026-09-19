<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzganq2ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qzganq2ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:oxygen-tank" {...props}></Icon>
