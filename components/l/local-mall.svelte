<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea8c8v_1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":456};
const content = `<path class="ea8c8v_1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-mall" {...props}></Icon>
