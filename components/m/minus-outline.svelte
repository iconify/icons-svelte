<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu7a8ewfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eu7a8ewfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:minus-outline" {...props}></Icon>
