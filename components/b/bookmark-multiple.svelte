<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idbul_oyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idbul_oyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-multiple" {...props}></Icon>
