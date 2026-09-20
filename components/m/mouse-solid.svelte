<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm999wbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="zm999wbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mouse-solid" {...props}></Icon>
