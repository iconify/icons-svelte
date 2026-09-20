<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l53ai8qjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l53ai8qjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:edge" {...props}></Icon>
