<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z17k1cbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z17k1cbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-e-circle-outline" {...props}></Icon>
