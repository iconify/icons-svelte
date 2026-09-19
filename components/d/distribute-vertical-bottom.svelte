<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2f33912z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2f33912z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:distribute-vertical-bottom" {...props}></Icon>
