<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiw-50w9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tiw-50w9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:milk-filled" {...props}></Icon>
