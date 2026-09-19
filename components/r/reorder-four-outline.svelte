<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v910tplip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v910tplip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reorder-four-outline" {...props}></Icon>
