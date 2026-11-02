<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sim8i5tck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sim8i5tck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-circle-line" {...props}></Icon>
