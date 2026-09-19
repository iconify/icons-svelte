<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irpgc2biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":750};
const content = `<path class="irpgc2biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:image" {...props}></Icon>
