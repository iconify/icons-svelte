<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4r2-ed2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4r2-ed2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:google-hangouts-alt" {...props}></Icon>
