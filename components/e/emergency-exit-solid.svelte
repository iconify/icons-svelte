<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp3a3pb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bp3a3pb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:emergency-exit-solid" {...props}></Icon>
