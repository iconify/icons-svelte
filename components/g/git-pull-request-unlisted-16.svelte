<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pztiz2epx.css';
import '../../css/u/ur-nm2blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pztiz2epx"/><path class="ur-nm2blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-pull-request-unlisted-16" {...props}></Icon>
