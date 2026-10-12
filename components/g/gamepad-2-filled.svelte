<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tira8ib7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tira8ib7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gamepad-2-filled" {...props}></Icon>
