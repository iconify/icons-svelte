<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m41pis-hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m41pis-hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:columns-2" {...props}></Icon>
