<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sao3gljiv.css';
import '../../css/a/agnu50b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sao3gljiv"/><path class="agnu50b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-brightgauge" {...props}></Icon>
