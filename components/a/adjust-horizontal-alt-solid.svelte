<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8eym3n7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y8eym3n7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:adjust-horizontal-alt-solid" {...props}></Icon>
