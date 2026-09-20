<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e59lt6b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e59lt6b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:measure-filled" {...props}></Icon>
