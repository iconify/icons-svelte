<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao_b-wo7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao_b-wo7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dhl" {...props}></Icon>
