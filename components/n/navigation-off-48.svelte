<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es3sj_btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="es3sj_btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:navigation-off-48" {...props}></Icon>
