<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es9lm-b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="es9lm-b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:code" {...props}></Icon>
