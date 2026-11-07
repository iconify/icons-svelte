<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oey6ny_di.css';
import '../../css/u/uv5m79ypg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oey6ny_di"/><path class="uv5m79ypg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-crack-bold" {...props}></Icon>
