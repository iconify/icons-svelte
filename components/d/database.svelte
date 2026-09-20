<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-wun7bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r-wun7bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:database" {...props}></Icon>
