<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr9yi2ure.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="lr9yi2ure"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nextjs-solid" {...props}></Icon>
