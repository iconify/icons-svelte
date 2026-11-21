<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3c-5acjg.css';
import '../../css/g/g5wxtpvfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3c-5acjg"/><path class="g5wxtpvfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layers-arrow-down-filled" {...props}></Icon>
