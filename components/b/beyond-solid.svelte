<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozfan2bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozfan2bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:beyond-solid" {...props}></Icon>
