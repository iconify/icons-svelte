<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tplczvb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tplczvb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:club" {...props}></Icon>
