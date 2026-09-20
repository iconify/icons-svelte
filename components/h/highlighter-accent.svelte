<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t81o7zwgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t81o7zwgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:highlighter-accent" {...props}></Icon>
