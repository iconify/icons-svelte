<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9nso0bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u9nso0bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:color-palette-flat" {...props}></Icon>
