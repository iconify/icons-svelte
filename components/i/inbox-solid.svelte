<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg43xbcaj.css';
import '../../css/i/itvcutb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lg43xbcaj"/><path class="itvcutb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:inbox-solid" {...props}></Icon>
