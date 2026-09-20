<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ityqu6bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ityqu6bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:refresh-alt" {...props}></Icon>
