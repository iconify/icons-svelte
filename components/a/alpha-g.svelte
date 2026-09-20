<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re84pcc3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re84pcc3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-g" {...props}></Icon>
