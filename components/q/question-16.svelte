<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1vphgcsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t1vphgcsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:question-16" {...props}></Icon>
