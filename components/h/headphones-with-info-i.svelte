<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eftoyqbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eftoyqbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:headphones-with-info-i" {...props}></Icon>
