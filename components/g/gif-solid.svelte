<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro2bxgb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ro2bxgb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gif-solid" {...props}></Icon>
