<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebspqb8ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ebspqb8ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-plus-outline" {...props}></Icon>
