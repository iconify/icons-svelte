<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyx9a9liv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyx9a9liv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cylinder-2-line" {...props}></Icon>
