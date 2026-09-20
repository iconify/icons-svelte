<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my72sn3_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my72sn3_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:currency-line" {...props}></Icon>
