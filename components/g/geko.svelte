<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-rp8ccxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-rp8ccxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:geko" {...props}></Icon>
