<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lreyzbrap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lreyzbrap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:comment" {...props}></Icon>
