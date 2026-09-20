<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv25lc1is.css';
import '../../css/e/ewgywhc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tv25lc1is"/><path class="ewgywhc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-pull" {...props}></Icon>
