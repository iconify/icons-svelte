<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csip7ekyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":512};
const content = `<path class="csip7ekyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cpcdosc" {...props}></Icon>
