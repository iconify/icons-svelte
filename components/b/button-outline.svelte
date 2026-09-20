<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd1p3qxtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cd1p3qxtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:button-outline" {...props}></Icon>
