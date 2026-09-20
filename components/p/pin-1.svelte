<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slo_ucbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slo_ucbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pin-1" {...props}></Icon>
