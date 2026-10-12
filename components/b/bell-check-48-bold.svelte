<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0__5rb2x.css';
import '../../css/o/ors50g_vw.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y0__5rb2x"/><path class="ors50g_vw"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-check-48-bold" {...props}></Icon>
