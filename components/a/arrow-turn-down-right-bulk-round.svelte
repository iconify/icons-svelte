<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrec87wmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrec87wmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-down-right-bulk-round" {...props}></Icon>
