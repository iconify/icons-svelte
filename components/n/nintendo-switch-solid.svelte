<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha9b68b0m.css';
import '../../css/f/fjxvhi0bo.css';
import '../../css/f/ftf34c06p.css';
import '../../css/l/l2ptp5l2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ha9b68b0m"/><path clip-rule="evenodd" class="fjxvhi0bo"/><path class="ftf34c06p"/><path clip-rule="evenodd" class="l2ptp5l2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nintendo-switch-solid" {...props}></Icon>
