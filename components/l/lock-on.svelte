<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nxnw64b0f.css';
import '../../css/f/f2g_8ms-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="nxnw64b0f"/><path class="f2g_8ms-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:lock-on" {...props}></Icon>
