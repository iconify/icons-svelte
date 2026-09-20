<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rthyrpbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rthyrpbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-sharp-fill" {...props}></Icon>
