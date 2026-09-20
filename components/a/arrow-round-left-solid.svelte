<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8uhqvtoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y8uhqvtoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-round-left-solid" {...props}></Icon>
