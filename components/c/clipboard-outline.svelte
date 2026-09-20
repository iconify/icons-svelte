<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0wdx9ywn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v0wdx9ywn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-outline" {...props}></Icon>
