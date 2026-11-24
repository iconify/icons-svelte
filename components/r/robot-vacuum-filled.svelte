<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf-5ik2ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lf-5ik2ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:robot-vacuum-filled" {...props}></Icon>
