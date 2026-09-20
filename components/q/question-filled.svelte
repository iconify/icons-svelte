<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5q7mwbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k5q7mwbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:question-filled" {...props}></Icon>
