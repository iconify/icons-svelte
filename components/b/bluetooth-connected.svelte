<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjboygbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjboygbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bluetooth-connected" {...props}></Icon>
