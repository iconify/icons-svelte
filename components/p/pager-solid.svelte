<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awox36b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="awox36b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pager-solid" {...props}></Icon>
