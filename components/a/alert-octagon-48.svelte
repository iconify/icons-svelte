<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hotj8abpa.css';
import '../../css/l/ls15nzj_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hotj8abpa"/><path class="ls15nzj_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-octagon-48" {...props}></Icon>
