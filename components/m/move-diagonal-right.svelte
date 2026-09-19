<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6uzf-99s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6uzf-99s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:move-diagonal-right" {...props}></Icon>
