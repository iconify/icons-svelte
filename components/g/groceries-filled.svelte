<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyz221lmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyz221lmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:groceries-filled" {...props}></Icon>
