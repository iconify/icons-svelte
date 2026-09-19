<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze75ltbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze75ltbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:drop-invert" {...props}></Icon>
