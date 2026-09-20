<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw9lf_b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aw9lf_b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-reload-vertical-2-solid" {...props}></Icon>
