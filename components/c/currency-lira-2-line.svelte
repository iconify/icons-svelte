<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml6p7i4lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml6p7i4lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-lira-2-line" {...props}></Icon>
