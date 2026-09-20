<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drupv_sdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drupv_sdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coins-minus" {...props}></Icon>
