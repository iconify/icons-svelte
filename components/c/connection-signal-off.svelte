<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on0krzm9t.css';
import '../../css/w/wdxgscteg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="on0krzm9t"/><path class="wdxgscteg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connection-signal-off" {...props}></Icon>
