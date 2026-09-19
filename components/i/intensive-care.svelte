<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1py9j2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq1py9j2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:intensive-care" {...props}></Icon>
