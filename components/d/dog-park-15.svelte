<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9a8azbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z9a8azbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:dog-park-15" {...props}></Icon>
