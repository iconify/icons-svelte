<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za0lhs10d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za0lhs10d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:refresh" {...props}></Icon>
