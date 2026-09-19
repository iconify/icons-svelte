<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6f9hxbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6f9hxbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:brackets" {...props}></Icon>
