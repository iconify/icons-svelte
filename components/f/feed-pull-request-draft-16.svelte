<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg_pavb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gg_pavb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-pull-request-draft-16" {...props}></Icon>
