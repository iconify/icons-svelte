<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fujt1ib7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="fujt1ib7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:inbox" {...props}></Icon>
