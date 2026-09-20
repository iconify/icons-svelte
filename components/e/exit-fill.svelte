<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxm448b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxm448b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exit-fill" {...props}></Icon>
