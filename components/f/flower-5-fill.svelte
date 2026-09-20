<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdf3tlb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdf3tlb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-5-fill" {...props}></Icon>
