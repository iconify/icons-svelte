<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izxba7fqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izxba7fqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:draw-inside" {...props}></Icon>
