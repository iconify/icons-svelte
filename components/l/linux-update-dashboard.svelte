<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eisknabqx.css';
import '../../css/h/hawpsccml.css';
import '../../css/x/xg9h40s8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eisknabqx"/><path class="hawpsccml"/><path class="xg9h40s8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linux-update-dashboard" {...props}></Icon>
