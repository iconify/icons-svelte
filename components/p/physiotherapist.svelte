<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiwq88sdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yiwq88sdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:physiotherapist" {...props}></Icon>
