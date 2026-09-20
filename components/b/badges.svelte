<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es3nb9bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es3nb9bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badges" {...props}></Icon>
