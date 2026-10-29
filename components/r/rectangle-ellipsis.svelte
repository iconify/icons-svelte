<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dlemphk8j.css';
import '../../css/i/i76dh14xw.css';
import '../../css/g/gj0zhrbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="dlemphk8j"/><path class="i76dh14xw"/><path class="gj0zhrbiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rectangle-ellipsis" {...props}></Icon>
