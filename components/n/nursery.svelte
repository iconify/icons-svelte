<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxk03wbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxk03wbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:nursery" {...props}></Icon>
