<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo9kk2b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zo9kk2b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:decorate-filled" {...props}></Icon>
