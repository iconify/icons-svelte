<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxraj1upd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxraj1upd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mug" {...props}></Icon>
