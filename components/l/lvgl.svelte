<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mposaj9da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mposaj9da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lvgl" {...props}></Icon>
