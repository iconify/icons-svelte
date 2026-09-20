<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snt803bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="snt803bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pie-chart-solid" {...props}></Icon>
