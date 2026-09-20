<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b52cj7bic.css';
import '../../css/d/de917sbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b52cj7bic"/><path class="de917sbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:monistic-logo" {...props}></Icon>
