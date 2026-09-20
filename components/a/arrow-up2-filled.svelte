<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brj23qz8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brj23qz8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up2-filled" {...props}></Icon>
