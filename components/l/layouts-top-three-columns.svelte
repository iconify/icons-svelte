<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxfn37b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxfn37b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:layouts-top-three-columns" {...props}></Icon>
