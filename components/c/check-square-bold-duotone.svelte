<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/s/sd8x9j4es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="sd8x9j4es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-square-bold-duotone" {...props}></Icon>
