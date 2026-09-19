<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc8fo5bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fc8fo5bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-remove-fill-16" {...props}></Icon>
