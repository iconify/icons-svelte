<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwcqqit1h.css';
import '../../css/c/cpstsachi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mwcqqit1h"/><path class="cpstsachi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:db2-buffer-pool" {...props}></Icon>
