<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnpqf24zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mnpqf24zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-pull-request-open-16" {...props}></Icon>
