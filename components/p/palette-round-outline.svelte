<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muwff1hjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="muwff1hjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-round-outline" {...props}></Icon>
