<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy3u8dwwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy3u8dwwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:margin-right-filled" {...props}></Icon>
