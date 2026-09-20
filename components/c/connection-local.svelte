<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guukbbb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="guukbbb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connection-local" {...props}></Icon>
