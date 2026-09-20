<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jinfwpbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jinfwpbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:canister-vacuum-cleaner" {...props}></Icon>
