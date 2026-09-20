<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amkv8ubhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="amkv8ubhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:book-reading-solid" {...props}></Icon>
