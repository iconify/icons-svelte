<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw8n9btnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw8n9btnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:dribbble-solid" {...props}></Icon>
