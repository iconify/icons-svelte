<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hieikacsf.css';
import '../../css/d/dp-b6abae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hieikacsf"/><path class="dp-b6abae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:creative-commons" {...props}></Icon>
