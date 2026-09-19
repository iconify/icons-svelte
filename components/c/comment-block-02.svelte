<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elcyv1bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elcyv1bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:comment-block-02" {...props}></Icon>
