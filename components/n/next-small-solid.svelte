<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx4jh9g-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fx4jh9g-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:next-small-solid" {...props}></Icon>
