<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6mdaccda.css';
import '../../css/m/m79b16c6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6mdaccda"/><path class="m79b16c6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:increasefontsize" {...props}></Icon>
