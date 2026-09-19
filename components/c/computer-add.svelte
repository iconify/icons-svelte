<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjy99ybww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjy99ybww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:computer-add" {...props}></Icon>
