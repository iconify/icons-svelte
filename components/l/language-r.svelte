<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js_zqcfan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js_zqcfan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-r" {...props}></Icon>
