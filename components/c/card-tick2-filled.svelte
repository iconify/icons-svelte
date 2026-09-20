<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8_y_zb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8_y_zb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-tick2-filled" {...props}></Icon>
