<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olf7scbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olf7scbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:robot" {...props}></Icon>
