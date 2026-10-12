<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r59jsbmuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r59jsbmuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:palette-filled" {...props}></Icon>
