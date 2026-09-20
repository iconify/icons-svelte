<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x63i9lbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x63i9lbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:index-open" {...props}></Icon>
