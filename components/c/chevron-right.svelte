<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2yoxlbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2yoxlbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:chevron-right" {...props}></Icon>
