<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw5x7qc2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dw5x7qc2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chrome-cast-filled" {...props}></Icon>
