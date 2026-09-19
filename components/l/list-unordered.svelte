<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4yxh5fbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t4yxh5fbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:list-unordered" {...props}></Icon>
