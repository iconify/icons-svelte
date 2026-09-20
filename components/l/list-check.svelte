<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh4-4ybqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh4-4ybqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:list-check" {...props}></Icon>
