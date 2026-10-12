<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5d8grbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5d8grbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:laptop-minimal-filled" {...props}></Icon>
