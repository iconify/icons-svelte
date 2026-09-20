<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqt9i-bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cqt9i-bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-to-down-bracket" {...props}></Icon>
