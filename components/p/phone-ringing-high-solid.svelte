<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax1grob-r.css';
import '../../css/x/x97sh721c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax1grob-r"/><path class="x97sh721c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:phone-ringing-high-solid" {...props}></Icon>
