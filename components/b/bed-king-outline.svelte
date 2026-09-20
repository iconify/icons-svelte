<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfkv-rb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfkv-rb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-king-outline" {...props}></Icon>
