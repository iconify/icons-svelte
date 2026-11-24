<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug3di98ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ug3di98ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:broccoli-filled" {...props}></Icon>
