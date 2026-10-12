<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9c6w6k3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9c6w6k3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-pile-filled" {...props}></Icon>
