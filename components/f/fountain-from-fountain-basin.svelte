<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhdgicbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hhdgicbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fountain-from-fountain-basin" {...props}></Icon>
