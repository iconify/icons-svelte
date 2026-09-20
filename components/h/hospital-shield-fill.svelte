<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6pf4lbun.css';
import '../../css/r/rqbyrwbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6pf4lbun"/><path class="rqbyrwbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:hospital-shield-fill" {...props}></Icon>
