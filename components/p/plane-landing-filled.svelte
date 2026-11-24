<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zni3kgb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zni3kgb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:plane-landing-filled" {...props}></Icon>
