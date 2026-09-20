<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xd3ta3d8r.css';
import '../../css/y/ytlnqnvjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path clip-rule="evenodd" class="xd3ta3d8r"/><path vector-effect="non-scaling-stroke" class="ytlnqnvjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:caution-filled" {...props}></Icon>
