<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kar4sbb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kar4sbb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:frames" {...props}></Icon>
