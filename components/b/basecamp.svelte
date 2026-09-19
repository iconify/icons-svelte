<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjv5ijdmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tjv5ijdmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:basecamp" {...props}></Icon>
