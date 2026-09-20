<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1k18lfcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k1k18lfcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:ai-model-16" {...props}></Icon>
