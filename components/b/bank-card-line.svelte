<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltns5k4cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltns5k4cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bank-card-line" {...props}></Icon>
