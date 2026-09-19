<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqykk_bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqykk_bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:extractor-fan" {...props}></Icon>
