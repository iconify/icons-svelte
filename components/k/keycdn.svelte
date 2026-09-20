<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt7jfflff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yt7jfflff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:keycdn" {...props}></Icon>
