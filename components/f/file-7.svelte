<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc0uk0c4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rc0uk0c4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-7" {...props}></Icon>
