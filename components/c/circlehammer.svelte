<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvuvnwh7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kvuvnwh7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlehammer" {...props}></Icon>
