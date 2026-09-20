<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5_jscbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t5_jscbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:insert-side-solid" {...props}></Icon>
