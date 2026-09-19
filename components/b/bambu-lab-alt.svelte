<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdy1rebht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdy1rebht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bambu-lab-alt" {...props}></Icon>
