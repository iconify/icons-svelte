<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amohcgtzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amohcgtzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-filled" {...props}></Icon>
