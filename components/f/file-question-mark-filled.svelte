<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1pb52z0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m1pb52z0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-question-mark-filled" {...props}></Icon>
