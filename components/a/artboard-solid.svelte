<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1beksb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m1beksb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:artboard-solid" {...props}></Icon>
