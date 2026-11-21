<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkqd60bly.css';
import '../../css/y/y_icihb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkqd60bly"/><path class="y_icihb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-cog-filled" {...props}></Icon>
