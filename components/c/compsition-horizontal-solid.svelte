<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7m83wb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g7m83wb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:compsition-horizontal-solid" {...props}></Icon>
