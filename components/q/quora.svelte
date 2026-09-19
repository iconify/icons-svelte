<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/y_40xtlgh.css';
import '../../css/w/w3u6i5b1c.css';
import '../../css/g/go5s9wb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="y_40xtlgh"/><path class="w3u6i5b1c"/><path class="go5s9wb5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:quora" {...props}></Icon>
