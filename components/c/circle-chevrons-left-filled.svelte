<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh-7vl_5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh-7vl_5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-chevrons-left-filled" {...props}></Icon>
