<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2jxgcc7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2jxgcc7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hard-drive-sharp-fill" {...props}></Icon>
