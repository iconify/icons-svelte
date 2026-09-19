<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_et0-cib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_et0-cib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:mobile-vibration" {...props}></Icon>
