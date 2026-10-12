<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa_mvlblm.css';
import '../../css/f/fubpiudof.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa_mvlblm"/><path class="fubpiudof"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-braces-corner-filled" {...props}></Icon>
