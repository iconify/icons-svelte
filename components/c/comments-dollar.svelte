<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_3ujp46z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t_3ujp46z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:comments-dollar" {...props}></Icon>
