<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-3vf829q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-3vf829q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:lock-rotation-solid" {...props}></Icon>
