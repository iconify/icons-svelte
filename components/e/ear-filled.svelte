<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeiweu1nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xeiweu1nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ear-filled" {...props}></Icon>
