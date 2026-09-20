<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu4i-n43a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu4i-n43a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-x" {...props}></Icon>
