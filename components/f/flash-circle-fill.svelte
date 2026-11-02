<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqy-tacas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqy-tacas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flash-circle-fill" {...props}></Icon>
