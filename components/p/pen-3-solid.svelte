<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9-tx9bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l9-tx9bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pen-3-solid" {...props}></Icon>
