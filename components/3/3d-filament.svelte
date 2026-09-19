<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_ae8_txj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ae8_txj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:3d-filament" {...props}></Icon>
