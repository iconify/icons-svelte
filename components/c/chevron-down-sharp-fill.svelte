<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z64_rrb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z64_rrb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevron-down-sharp-fill" {...props}></Icon>
