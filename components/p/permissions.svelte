<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7sr6ubzr.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/db7dp1qih.css';
import '../../css/k/kcyfzcebs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><g class="d2kvgvbvc"><path class="db7dp1qih"/><path class="kcyfzcebs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:permissions" {...props}></Icon>
