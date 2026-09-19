<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo8ud7_4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mo8ud7_4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-ttf" {...props}></Icon>
