<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvlv85b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nvlv85b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-review-16" {...props}></Icon>
