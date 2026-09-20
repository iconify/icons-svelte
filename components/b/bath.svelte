<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agz0m6b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="agz0m6b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bath" {...props}></Icon>
