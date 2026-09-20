<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j73ug6bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j73ug6bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-transfer-diagonal-1-solid" {...props}></Icon>
