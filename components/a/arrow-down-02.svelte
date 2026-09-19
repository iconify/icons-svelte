<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft9suwbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft9suwbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-02" {...props}></Icon>
