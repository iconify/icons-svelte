<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/m/m_wng7bri.css';
import '../../css/l/lt2add1gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="m_wng7bri"/><path class="lt2add1gd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-shield-line" {...props}></Icon>
