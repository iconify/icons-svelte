<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbiy5tpwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbiy5tpwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fish-off" {...props}></Icon>
