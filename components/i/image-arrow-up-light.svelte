<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r70_bowor.css';
import '../../css/j/j73_9_mpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r70_bowor"/><path class="j73_9_mpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-arrow-up-light" {...props}></Icon>
