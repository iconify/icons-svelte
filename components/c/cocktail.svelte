<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8yqr8m5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h8yqr8m5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cocktail" {...props}></Icon>
