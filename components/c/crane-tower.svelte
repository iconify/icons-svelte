<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbszl1yhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbszl1yhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:crane-tower" {...props}></Icon>
