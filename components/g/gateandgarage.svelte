<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc50rmbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc50rmbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:gateandgarage" {...props}></Icon>
