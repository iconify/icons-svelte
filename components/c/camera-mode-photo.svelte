<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pmt5d56mi.css';
import '../../css/h/hs5-acbpc.css';
import '../../css/y/y64_-73hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pmt5d56mi"/><path class="hs5-acbpc"/><path class="y64_-73hw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:camera-mode-photo" {...props}></Icon>
