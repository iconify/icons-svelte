<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4b0s9bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t4b0s9bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:portrait-lock-solid" {...props}></Icon>
