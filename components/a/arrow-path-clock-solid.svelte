<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv_vv6bcm.css';
import '../../css/h/h0l56x3zd.css';
import '../../css/j/jno6wvb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nv_vv6bcm"><path class="h0l56x3zd"/><path class="jno6wvb7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-clock-solid" {...props}></Icon>
