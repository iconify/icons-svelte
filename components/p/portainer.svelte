<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e54-pvbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e54-pvbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:portainer" {...props}></Icon>
