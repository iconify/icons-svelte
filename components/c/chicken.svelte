<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3_gg71sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="q3_gg71sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:chicken" {...props}></Icon>
