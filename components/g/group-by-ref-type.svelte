<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmk6lwbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tmk6lwbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:group-by-ref-type" {...props}></Icon>
