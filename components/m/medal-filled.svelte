<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0qfuhvsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e0qfuhvsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:medal-filled" {...props}></Icon>
