<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slr52vb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slr52vb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:handheld-filled" {...props}></Icon>
