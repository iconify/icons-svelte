<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saih6fxnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saih6fxnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dartboard" {...props}></Icon>
