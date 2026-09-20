<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve5zjyb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ve5zjyb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-flat-outline" {...props}></Icon>
