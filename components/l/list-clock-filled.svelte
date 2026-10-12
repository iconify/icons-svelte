<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szg_xwy0s.css';
import '../../css/e/eozjh4bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="szg_xwy0s"/><path class="eozjh4bxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:list-clock-filled" {...props}></Icon>
