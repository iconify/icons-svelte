<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k56cacc_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k56cacc_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:luggage-line" {...props}></Icon>
