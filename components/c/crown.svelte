<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_boytb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1472};
const content = `<path class="g_boytb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:crown" {...props}></Icon>
