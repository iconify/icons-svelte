<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty3029wgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ty3029wgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:female-sharp" {...props}></Icon>
