<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2fpl2orn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2fpl2orn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-minus-bold" {...props}></Icon>
