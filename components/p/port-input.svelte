<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyto8pb-r.css';
import '../../css/q/qq9jsubwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gyto8pb-r"/><path class="qq9jsubwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:port-input" {...props}></Icon>
