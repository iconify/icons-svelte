<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y82zzkv5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y82zzkv5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-x-filled" {...props}></Icon>
