<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiupigchs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uiupigchs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:eclipse-filled" {...props}></Icon>
