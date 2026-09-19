<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-4g368hm.css';
import '../../css/s/s11f4ob4t.css';
import '../../css/e/ew4v2q7dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="y-4g368hm"><path class="s11f4ob4t"/><path class="ew4v2q7dx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:glowing-star" {...props}></Icon>
