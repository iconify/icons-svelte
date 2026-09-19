<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewspl0ckp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ewspl0ckp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mail" {...props}></Icon>
