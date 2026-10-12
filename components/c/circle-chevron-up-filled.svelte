<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvihl5yzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uvihl5yzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-chevron-up-filled" {...props}></Icon>
