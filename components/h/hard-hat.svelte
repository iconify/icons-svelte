<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqm3hwbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqm3hwbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hard-hat" {...props}></Icon>
