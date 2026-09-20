<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7r03-bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h7r03-bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-intersect-solid" {...props}></Icon>
