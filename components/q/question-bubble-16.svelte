<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n26w-wbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n26w-wbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:question-bubble-16" {...props}></Icon>
