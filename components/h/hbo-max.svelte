<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dte3qfcbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dte3qfcbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hbo-max" {...props}></Icon>
