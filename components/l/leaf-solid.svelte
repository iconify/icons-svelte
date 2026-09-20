<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkq-jjbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qkq-jjbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:leaf-solid" {...props}></Icon>
