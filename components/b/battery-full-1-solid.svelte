<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixcqlbc8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ixcqlbc8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-full-1-solid" {...props}></Icon>
