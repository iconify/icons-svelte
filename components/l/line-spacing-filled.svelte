<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvb8ck75z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvb8ck75z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:line-spacing-filled" {...props}></Icon>
