<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkyy27shr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkyy27shr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fungus-outline" {...props}></Icon>
