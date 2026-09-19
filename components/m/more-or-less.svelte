<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h93bu-h8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h93bu-h8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-or-less" {...props}></Icon>
