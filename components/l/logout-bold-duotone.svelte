<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnqp7eb9p.css';
import '../../css/t/tsxl3yofp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnqp7eb9p"/><path clip-rule="evenodd" class="tsxl3yofp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-bold-duotone" {...props}></Icon>
