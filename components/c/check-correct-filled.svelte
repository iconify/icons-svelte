<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4eklxbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z4eklxbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:check-correct-filled" {...props}></Icon>
