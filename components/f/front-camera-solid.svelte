<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubcjzxw5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ubcjzxw5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:front-camera-solid" {...props}></Icon>
