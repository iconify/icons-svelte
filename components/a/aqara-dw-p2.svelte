<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtca2iexn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtca2iexn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-dw-p2" {...props}></Icon>
