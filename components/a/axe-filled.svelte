<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl_iuno7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sl_iuno7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:axe-filled" {...props}></Icon>
