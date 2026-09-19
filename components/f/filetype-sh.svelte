<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5uc7i-cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g5uc7i-cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-sh" {...props}></Icon>
