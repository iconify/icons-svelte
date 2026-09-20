<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex6pcz9lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ex6pcz9lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:maximize-2-solid" {...props}></Icon>
