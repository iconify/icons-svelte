<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy7wskbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oy7wskbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-left-square-fill" {...props}></Icon>
