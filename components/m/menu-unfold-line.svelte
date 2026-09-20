<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdsn14zrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdsn14zrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-unfold-line" {...props}></Icon>
