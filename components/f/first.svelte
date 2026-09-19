<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/talqtbtdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="talqtbtdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:first" {...props}></Icon>
