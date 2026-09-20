<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rao67hbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rao67hbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:discount" {...props}></Icon>
