<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u26dwrbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u26dwrbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-2" {...props}></Icon>
