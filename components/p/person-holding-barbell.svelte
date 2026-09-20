<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg24q37mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jg24q37mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-holding-barbell" {...props}></Icon>
