<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-3i5bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v4-3i5bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:left-align-filled" {...props}></Icon>
