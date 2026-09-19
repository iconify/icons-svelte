<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll5l_dukg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ll5l_dukg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:loadingflowcw" {...props}></Icon>
