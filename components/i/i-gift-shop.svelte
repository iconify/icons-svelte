<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sucysfikq.css';
import '../../css/r/rifcqzbni.css';
import '../../css/n/nigjfvbya.css';
import '../../css/i/ibgenzjqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="sucysfikq"/><path class="rifcqzbni"/><path class="nigjfvbya"/><path class="ibgenzjqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-gift-shop" {...props}></Icon>
