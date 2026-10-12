<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq_frzb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wq_frzb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-power-filled" {...props}></Icon>
