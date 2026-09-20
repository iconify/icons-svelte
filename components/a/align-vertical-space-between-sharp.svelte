<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e171jac_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e171jac_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-space-between-sharp" {...props}></Icon>
