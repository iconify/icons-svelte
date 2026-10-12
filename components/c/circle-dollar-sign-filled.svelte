<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9eo20bcx.css';
import '../../css/p/p5f1kab4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9eo20bcx"/><path clip-rule="evenodd" class="p5f1kab4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-dollar-sign-filled" {...props}></Icon>
