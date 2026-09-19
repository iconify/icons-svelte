<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3xob38rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3xob38rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-right-04" {...props}></Icon>
