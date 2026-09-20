<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbkf4vbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cbkf4vbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:pay" {...props}></Icon>
