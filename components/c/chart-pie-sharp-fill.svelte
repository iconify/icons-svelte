<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pby7ywbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pby7ywbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-pie-sharp-fill" {...props}></Icon>
