<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1xeb4bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1xeb4bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-lines-sharp" {...props}></Icon>
