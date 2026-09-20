<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aukdzwhab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aukdzwhab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:headset-solid" {...props}></Icon>
