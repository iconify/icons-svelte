<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0iflzkqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0iflzkqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-off-sharp" {...props}></Icon>
