<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlv6aib1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlv6aib1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:arrow-reload-horizontal-2-flat" {...props}></Icon>
