<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aapi2lbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aapi2lbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:gear-16" {...props}></Icon>
