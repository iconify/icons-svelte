<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnl6k-emx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bnl6k-emx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:drink-cup-with-straw-and-boba" {...props}></Icon>
