<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zefbo4jxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zefbo4jxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:magentatv-alt" {...props}></Icon>
