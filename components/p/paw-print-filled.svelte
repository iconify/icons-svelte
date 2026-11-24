<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uopljoblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uopljoblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:paw-print-filled" {...props}></Icon>
