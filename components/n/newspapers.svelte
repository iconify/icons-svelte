<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd2oakb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd2oakb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:newspapers" {...props}></Icon>
