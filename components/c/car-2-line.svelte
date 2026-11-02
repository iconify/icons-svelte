<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgimc7f1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgimc7f1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-2-line" {...props}></Icon>
