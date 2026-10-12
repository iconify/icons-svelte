<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy0h67bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uy0h67bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-arrow-right-filled" {...props}></Icon>
