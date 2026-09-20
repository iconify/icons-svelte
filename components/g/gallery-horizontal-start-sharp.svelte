<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rha8oacpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rha8oacpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-horizontal-start-sharp" {...props}></Icon>
