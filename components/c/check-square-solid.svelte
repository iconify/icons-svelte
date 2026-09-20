<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyz4uac8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jyz4uac8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:check-square-solid" {...props}></Icon>
