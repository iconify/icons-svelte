<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc0nuhbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cc0nuhbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:data-transfer-sync" {...props}></Icon>
