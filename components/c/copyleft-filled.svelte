<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1ezadbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d1ezadbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:copyleft-filled" {...props}></Icon>
