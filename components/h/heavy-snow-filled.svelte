<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-he_lcqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a-he_lcqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:heavy-snow-filled" {...props}></Icon>
