<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu28debah.css';
import '../../css/d/divqy_2wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu28debah"/><path class="divqy_2wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-pen-line-filled" {...props}></Icon>
