<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c58930t5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c58930t5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:menu-endways-filled" {...props}></Icon>
