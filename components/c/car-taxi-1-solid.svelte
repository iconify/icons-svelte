<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9o022b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c9o022b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:car-taxi-1-solid" {...props}></Icon>
