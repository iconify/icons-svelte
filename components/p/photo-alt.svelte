<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/t1i4u809l.css';
import '../../css/j/j6miii01f.css';
import '../../css/s/sv9ccdysk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t1i4u809l"/><path class="j6miii01f"/><path class="sv9ccdysk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-alt" {...props}></Icon>
