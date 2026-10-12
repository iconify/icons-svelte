<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g57tje5ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g57tje5ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:door-closed-filled" {...props}></Icon>
