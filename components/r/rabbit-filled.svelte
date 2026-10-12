<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd3k9mbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd3k9mbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rabbit-filled" {...props}></Icon>
