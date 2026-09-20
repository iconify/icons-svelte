<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey68ddzco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ey68ddzco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:d-arrow-right" {...props}></Icon>
