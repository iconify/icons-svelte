<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-z9jebeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t-z9jebeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:left-bracket-and-cube" {...props}></Icon>
