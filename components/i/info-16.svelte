<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1igf8vwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s1igf8vwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:info-16" {...props}></Icon>
