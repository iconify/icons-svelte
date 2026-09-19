<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a07m1ch5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a07m1ch5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:measuring-cup" {...props}></Icon>
